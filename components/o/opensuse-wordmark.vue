<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/easitdb1p.css';
import '../../css/l/lndkxrb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="easitdb1p"/><path class="lndkxrb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opensuse-wordmark" /></template>
