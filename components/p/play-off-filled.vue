<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao_dv4bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_dv4bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:play-off-filled" /></template>
