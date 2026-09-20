<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4dk4o63l.css';
import '../../css/r/rit0h486c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4dk4o63l"/><path class="rit0h486c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-cancel-fill" /></template>
