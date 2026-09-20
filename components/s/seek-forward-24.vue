<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyzjw1bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyzjw1bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:seek-forward-24" /></template>
