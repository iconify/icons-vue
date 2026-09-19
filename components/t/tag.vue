<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvwf3uisn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvwf3uisn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tag" /></template>
