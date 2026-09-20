<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2nwvi2kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2nwvi2kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:staffbase" /></template>
