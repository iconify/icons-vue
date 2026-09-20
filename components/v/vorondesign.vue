<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx_vwr6rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx_vwr6rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vorondesign" /></template>
