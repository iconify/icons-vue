<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-hc8y_jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-hc8y_jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thermostat-box" /></template>
