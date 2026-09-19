<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd63t2zpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qd63t2zpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-off" /></template>
