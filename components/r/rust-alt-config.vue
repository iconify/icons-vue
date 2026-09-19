<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh7u9f3r.css';
import '../../css/v/v_9terb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><path class="v_9terb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rust-alt-config" /></template>
