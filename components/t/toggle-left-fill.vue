<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh5og7tnq.css';
import '../../css/f/f__7awrdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh5og7tnq"/><path class="f__7awrdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:toggle-left-fill" /></template>
