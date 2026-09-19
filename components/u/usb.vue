<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg9j1eb8x.css';
import '../../css/v/v71f_-age.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vg9j1eb8x"/><path class="v71f_-age"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:usb" /></template>
