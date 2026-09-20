<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxmaacp6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxmaacp6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:northwest-southeast-duotone" /></template>
