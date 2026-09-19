<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or6rs0b6f.css';
import '../../css/z/z7sl-6blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="z7sl-6blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:notification-slash" /></template>
