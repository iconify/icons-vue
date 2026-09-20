<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss7xuob1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7xuob1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nfc" /></template>
