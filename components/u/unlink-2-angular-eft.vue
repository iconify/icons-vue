<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbpbqzb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="gbpbqzb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:unlink-2-angular-eft" /></template>
