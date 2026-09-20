<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzuuxyv1b.css';
import '../../css/e/e9w0n4t1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzuuxyv1b"/><path class="e9w0n4t1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:movary" /></template>
