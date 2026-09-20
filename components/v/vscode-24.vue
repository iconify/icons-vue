<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvvy4hbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qvvy4hbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:vscode-24" /></template>
