<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz-nt3jcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz-nt3jcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sort" /></template>
