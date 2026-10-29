<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k75pbxo-h.css';
import '../../css/o/owfk9nbdh.css';
import '../../css/i/iqy1ivbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k75pbxo-h wm-k"/><path class="owfk9nbdh wm-a"/><path class="iqy1ivbzl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:percent" /></template>
