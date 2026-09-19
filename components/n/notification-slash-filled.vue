<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or6rs0b6f.css';
import '../../css/u/ua_yb7b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="ua_yb7b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:notification-slash-filled" /></template>
