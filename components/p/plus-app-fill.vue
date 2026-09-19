<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht_xe9bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ht_xe9bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-app-fill" /></template>
