<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sugnyfphq.css';
import '../../css/i/i9bnjpm9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sugnyfphq"/><path class="i9bnjpm9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xcm" /></template>
