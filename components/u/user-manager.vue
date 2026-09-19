<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfku7l3wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfku7l3wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:user-manager" /></template>
