<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bay1nz_kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bay1nz_kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:memories-line" /></template>
