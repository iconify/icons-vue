<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vob1vf30q.css';
import '../../css/c/cttr9cbpd.css';
import '../../css/h/hz2a1g29i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vob1vf30q"/><path class="cttr9cbpd"/><path clip-rule="evenodd" class="hz2a1g29i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-check-outline" /></template>
