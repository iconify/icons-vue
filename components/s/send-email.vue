<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e91abccpm.css';
import '../../css/b/bacg9dj7f.css';
import '../../css/x/x792okb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e91abccpm"/><path class="bacg9dj7f"/><path class="x792okb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:send-email" /></template>
