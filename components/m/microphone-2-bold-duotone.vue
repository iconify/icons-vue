<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue2-q7bvs.css';
import '../../css/v/v_lna_b8l.css';
import '../../css/q/q62hssb8w.css';
import '../../css/s/snl_-6b7g.css';
import '../../css/p/pi3quynir.css';
import '../../css/o/obev98o9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue2-q7bvs"/><path class="v_lna_b8l"/><path class="q62hssb8w"/><path class="snl_-6b7g"/><path class="pi3quynir"/><path class="obev98o9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-2-bold-duotone" /></template>
