<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b20yb556g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b20yb556g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:talos" /></template>
