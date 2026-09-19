<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyi-f8nlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":579.274,"height":1000};
const content = `<path class="xyi-f8nlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:odnoklassniki" /></template>
