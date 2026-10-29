<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl5uzhbhz.css';
import '../../css/a/a-8u3piaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="a-8u3piaa wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:plus-circle" /></template>
