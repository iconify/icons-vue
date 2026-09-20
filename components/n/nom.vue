<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6pex7q3c.css';
import '../../css/r/rgqpz_b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6pex7q3c"/><path class="rgqpz_b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nom" /></template>
