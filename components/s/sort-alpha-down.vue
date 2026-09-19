<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzdpjmbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zzdpjmbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-alpha-down" /></template>
