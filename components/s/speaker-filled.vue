<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2dmbzbpi.css';
import '../../css/l/l1v0zsvht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2dmbzbpi"/><path class="l1v0zsvht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:speaker-filled" /></template>
