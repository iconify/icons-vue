<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit0tnbsg.css';
import '../../css/t/tag3qab8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hit0tnbsg"/><path class="tag3qab8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:phone-ringing-low" /></template>
