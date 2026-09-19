<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qli42hr8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qli42hr8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:next-hub-max" /></template>
