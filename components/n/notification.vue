<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc5umne5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc5umne5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:notification" /></template>
