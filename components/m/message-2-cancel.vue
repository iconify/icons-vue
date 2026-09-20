<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnx0k3uqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnx0k3uqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-cancel" /></template>
