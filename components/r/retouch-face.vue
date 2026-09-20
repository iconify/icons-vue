<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6lsn5bzb.css';
import '../../css/j/j2c1c4b4t.css';
import '../../css/p/pyhe_fr8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6lsn5bzb"/><path class="j2c1c4b4t"/><path class="pyhe_fr8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:retouch-face" /></template>
