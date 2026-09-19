<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fibdm626q.css';
import '../../css/e/e71oo0bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fibdm626q"/><path class="e71oo0bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-skype-outline" /></template>
