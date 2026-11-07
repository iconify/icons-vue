<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv4wotbsh.css';
import '../../css/b/b133qtshg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv4wotbsh"/><path class="b133qtshg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-unread-bold-duotone" /></template>
