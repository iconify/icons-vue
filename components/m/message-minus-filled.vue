<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amqug9ayf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amqug9ayf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-minus-filled" /></template>
