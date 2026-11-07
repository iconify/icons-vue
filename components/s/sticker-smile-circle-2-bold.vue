<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mms9xzmvs.css';
import '../../css/a/a2h-5ubrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mms9xzmvs"/><path clip-rule="evenodd" class="a2h-5ubrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-circle-2-bold" /></template>
