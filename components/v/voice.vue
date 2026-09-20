<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtl_pwb1c.css';
import '../../css/b/bp9bjib7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtl_pwb1c"/><path class="bp9bjib7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:voice" /></template>
