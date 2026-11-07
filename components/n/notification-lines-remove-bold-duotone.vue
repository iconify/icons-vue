<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1b-v8rmi.css';
import '../../css/w/whbeue6my.css';
import '../../css/a/at92h2-kh.css';
import '../../css/c/ch9w-bbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b-v8rmi"/><path class="whbeue6my"/><path clip-rule="evenodd" class="at92h2-kh"/><path class="ch9w-bbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-lines-remove-bold-duotone" /></template>
