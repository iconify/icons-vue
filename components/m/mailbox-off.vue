<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt6741bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6741bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mailbox-off" /></template>
