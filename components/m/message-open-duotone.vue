<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnor7rbtu.css';
import '../../css/i/iim7l5brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnor7rbtu"/><path class="iim7l5brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-open-duotone" /></template>
