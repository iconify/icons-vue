<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt32cgb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt32cgb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:upload-line" /></template>
