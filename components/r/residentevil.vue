<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maj0_wbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="maj0_wbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:residentevil" /></template>
