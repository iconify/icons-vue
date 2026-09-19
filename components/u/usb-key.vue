<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07hkebjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q07hkebjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:usb-key" /></template>
