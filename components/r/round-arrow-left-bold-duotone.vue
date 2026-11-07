<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu-cc3sah.css';
import '../../css/q/qrog0acqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-cc3sah"/><path class="qrog0acqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-bold-duotone" /></template>
