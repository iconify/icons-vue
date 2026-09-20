<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l84h-5chk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l84h-5chk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-plus-sharp" /></template>
