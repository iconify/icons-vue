<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr2f8pbje.css';
import '../../css/c/ch9w-bbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr2f8pbje"/><path class="ch9w-bbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-remove-bold-duotone" /></template>
