<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9y477w0i.css';
import '../../css/c/cj0d3vbqu.css';
import '../../css/d/dvn5fybze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="cj0d3vbqu"/><path class="dvn5fybze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-check-bold-duotone" /></template>
