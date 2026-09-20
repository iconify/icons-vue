<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b70-wwoww.css';
import '../../css/v/vgzbicbpw.css';
import '../../css/i/ilgbhxbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b70-wwoww"/><path class="vgzbicbpw"/><path class="ilgbhxbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-defender-light" /></template>
