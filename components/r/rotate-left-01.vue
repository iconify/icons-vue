<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbf5-9nsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbf5-9nsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-left-01" /></template>
