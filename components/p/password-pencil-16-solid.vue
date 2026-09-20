<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md1qd5bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="md1qd5bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-pencil-16-solid" /></template>
