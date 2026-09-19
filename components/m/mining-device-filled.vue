<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_9hocblj.css';
import '../../css/j/jr2c_p1uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9hocblj"/><path clip-rule="evenodd" class="jr2c_p1uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:mining-device-filled" /></template>
