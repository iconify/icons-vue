<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_yj2gmv.css';
import '../../css/m/m6_8tzbzx.css';
import '../../css/l/lv8wzrvsk.css';
import '../../css/n/nsaobjj4n.css';
import '../../css/b/b_u8-y3gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_yj2gmv wm-k"/><path class="m6_8tzbzx wm-a"/><path class="lv8wzrvsk wm-k"/><path class="nsaobjj4n wm-k"/><path class="b_u8-y3gn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:school" /></template>
