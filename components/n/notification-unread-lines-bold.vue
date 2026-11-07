<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b133qtshg.css';
import '../../css/x/xc8aj3z1k.css';
import '../../css/b/b9e4xccvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b133qtshg"/><path clip-rule="evenodd" class="xc8aj3z1k"/><path clip-rule="evenodd" class="b9e4xccvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-unread-lines-bold" /></template>
