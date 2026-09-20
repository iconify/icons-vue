<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrf8tpm0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrf8tpm0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-6-fill" /></template>
