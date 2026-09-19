<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxgckcb1c.css';
import '../../css/w/w8tdd6b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxgckcb1c"/><path class="w8tdd6b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:subscription-management" /></template>
