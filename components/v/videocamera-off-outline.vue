<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh82fib1q.css';
import '../../css/j/jvt0l2akk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh82fib1q"/><path clip-rule="evenodd" class="jvt0l2akk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-off-outline" /></template>
