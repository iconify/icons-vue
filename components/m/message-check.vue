<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtixo6etk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtixo6etk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-check" /></template>
