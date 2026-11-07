<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mms9xzmvs.css';
import '../../css/g/gxzkh2b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mms9xzmvs"/><path class="gxzkh2b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-circle-bold-duotone" /></template>
