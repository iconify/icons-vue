<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0ca_zb6s.css';
import '../../css/e/e1e3xxbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="e1e3xxbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:settings-filled" /></template>
