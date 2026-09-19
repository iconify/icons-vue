<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0tu5dsyz.css';
import '../../css/i/if95wl24z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0tu5dsyz"/><path class="if95wl24z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-slash-filled" /></template>
