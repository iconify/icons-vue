<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0h6iq6ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0h6iq6ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-off-solid" /></template>
