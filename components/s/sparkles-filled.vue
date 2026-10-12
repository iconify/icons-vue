<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxur79b5t.css';
import '../../css/y/y95_zrbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxur79b5t"/><path class="y95_zrbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sparkles-filled" /></template>
