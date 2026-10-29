<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d43m7xz-l.css';
import '../../css/x/xf9s29b3q.css';
import '../../css/e/enuyxv0hd.css';
import '../../css/h/h03ww_9cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d43m7xz-l wm-k"/><path class="wm-a xf9s29b3q"/><path class="enuyxv0hd wm-a"/><path class="h03ww_9cz wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sliders" /></template>
