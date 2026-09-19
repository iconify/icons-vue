<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or6rs0b6f.css';
import '../../css/j/jbe-t4btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="jbe-t4btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-notification-filled" /></template>
