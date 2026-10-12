<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb_f6kbki.css';
import '../../css/z/zb_q1oboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb_f6kbki"/><path class="zb_q1oboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:touchpad-off-filled" /></template>
