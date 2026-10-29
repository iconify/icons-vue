<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syk1us2fg.css';
import '../../css/o/ob9_5nbbe.css';
import '../../css/g/gth95mb7o.css';
import '../../css/z/zxqj3r0da.css';
import '../../css/h/hff6qok6f.css';
import '../../css/a/agex9k6ym.css';
import '../../css/m/mu3xycbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syk1us2fg wm-shadow"/><path class="ob9_5nbbe wm-k"/><path class="gth95mb7o wm-k"/><path class="wm-k zxqj3r0da"/><path class="hff6qok6f wm-k"/><path class="agex9k6ym wm-k"/><path class="mu3xycbhf wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:panel-top" /></template>
