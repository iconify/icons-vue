<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjisd8szm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjisd8szm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:vertical-switch-long-light" /></template>
