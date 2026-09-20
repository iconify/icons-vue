<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or_6jdb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or_6jdb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:more-menu-line" /></template>
