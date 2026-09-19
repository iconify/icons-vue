<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-jn3bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":690};
const content = `<path class="bp-jn3bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:pc" /></template>
