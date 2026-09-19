<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4b96bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4b96bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-up" /></template>
