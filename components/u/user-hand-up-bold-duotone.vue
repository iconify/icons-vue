<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls12hhbch.css';
import '../../css/u/ugczn2boc.css';
import '../../css/j/j855t9sbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls12hhbch"/><path class="ugczn2boc"/><path class="j855t9sbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-hand-up-bold-duotone" /></template>
