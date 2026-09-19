<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzy0c9c2j.css';
import '../../css/j/j43vdgeku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzy0c9c2j"/><path class="j43vdgeku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-detail" /></template>
