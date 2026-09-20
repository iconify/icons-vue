<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf56cje1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf56cje1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:usb-sharp" /></template>
