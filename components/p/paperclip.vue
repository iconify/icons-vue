<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im7r0tykw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="im7r0tykw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:paperclip" /></template>
