<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh611i-hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh611i-hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:secure" /></template>
