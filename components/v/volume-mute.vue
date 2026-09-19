<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at9p0p48i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at9p0p48i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volume-mute" /></template>
