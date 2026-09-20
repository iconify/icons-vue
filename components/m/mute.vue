<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm69jwb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fm69jwb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:mute" /></template>
