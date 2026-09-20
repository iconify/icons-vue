<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uomcqqb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uomcqqb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:object-group" /></template>
