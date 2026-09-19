<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuznmyb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":480};
const content = `<path class="uuznmyb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:no-eye" /></template>
