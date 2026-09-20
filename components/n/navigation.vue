<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo5j-v08u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo5j-v08u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:navigation" /></template>
