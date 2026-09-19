<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp00o5b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp00o5b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:open-webui-alt" /></template>
