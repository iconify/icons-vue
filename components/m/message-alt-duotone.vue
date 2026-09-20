<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxayxvndo.css';
import '../../css/x/xfzudwcmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="nxayxvndo"/><path class="xfzudwcmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-alt-duotone" /></template>
