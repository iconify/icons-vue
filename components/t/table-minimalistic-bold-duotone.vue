<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nayqy1c_r.css';
import '../../css/k/kydc5glkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="kydc5glkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-minimalistic-bold-duotone" /></template>
