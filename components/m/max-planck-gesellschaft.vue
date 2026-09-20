<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abeczyp3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abeczyp3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:max-planck-gesellschaft" /></template>
