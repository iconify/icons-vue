<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-7ackjni.css';
import '../../css/h/h4a5d8u6i.css';
import '../../css/y/y-8n_fb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-7ackjni"/><path class="h4a5d8u6i"/><path clip-rule="evenodd" class="y-8n_fb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-bold" /></template>
