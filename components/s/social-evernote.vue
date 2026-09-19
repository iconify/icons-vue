<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmmcidcze.css';
import '../../css/t/tba5rlbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qmmcidcze"/><path class="tba5rlbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-evernote" /></template>
