<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1587w2qu.css';
import '../../css/o/ow15xdb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1587w2qu"/><path class="ow15xdb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-envelope-duotone" /></template>
