<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9xc7hwgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9xc7hwgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-only-one-to-zero-or-many" /></template>
