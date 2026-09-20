<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht5kbo4uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ht5kbo4uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:screwdriver-solid" /></template>
