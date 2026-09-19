<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngzg86xih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngzg86xih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-x-filled" /></template>
