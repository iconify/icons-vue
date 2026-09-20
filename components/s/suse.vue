<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odg1w-btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="odg1w-btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:suse" /></template>
