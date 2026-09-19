<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or6rs0b6f.css';
import '../../css/i/iku26qo3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="iku26qo3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-notification-filled" /></template>
