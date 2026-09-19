<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sddwh4xus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1020,"height":1024};
const content = `<path class="sddwh4xus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mute" /></template>
