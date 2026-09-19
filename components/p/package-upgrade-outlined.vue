<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewl61acth.css';
import '../../css/r/r58_0ub5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewl61acth"/><path class="r58_0ub5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:package-upgrade-outlined" /></template>
