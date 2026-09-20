<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj8o_xb5j.css';
import '../../css/m/mqstf9bxa.css';
import '../../css/x/xlvhy0vyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj8o_xb5j"/><path class="mqstf9bxa"/><path class="xlvhy0vyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:web-grid" /></template>
