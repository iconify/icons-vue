<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nayqy1c_r.css';
import '../../css/h/h0p33jbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="h0p33jbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-bold-duotone" /></template>
