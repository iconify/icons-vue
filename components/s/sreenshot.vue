<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veqikhb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="veqikhb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sreenshot" /></template>
