<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0s8dnbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="b0s8dnbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:menu-hamburger-1" /></template>
