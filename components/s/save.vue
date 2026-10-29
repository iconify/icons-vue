<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt0yw-b-f.css';
import '../../css/j/j6fm-zcrt.css';
import '../../css/p/pacun0b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zt0yw-b-f"/><path class="j6fm-zcrt wm-a"/><path class="pacun0b5f wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:save" /></template>
