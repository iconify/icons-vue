<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vusbhcbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vusbhcbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-eye-off" /></template>
