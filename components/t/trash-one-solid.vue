<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9-5dbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9-5dbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trash-one-solid" /></template>
