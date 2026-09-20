<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eov1yhx6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-question-sharp" /></template>
<style>
.eov1yhx6c {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m.43-4.62q.197-.198.197-.469t-.197-.468t-.468-.197t-.469.197t-.197.468t.197.468q.198.198.469.198t.468-.198m-.905-2.58h.885q.019-.255.057-.511t.164-.467q.169-.273.371-.501t.42-.44q.424-.444.756-.94t.332-1.16q0-.97-.738-1.607q-.737-.635-1.733-.635q-.847 0-1.538.45T9.496 9.177l.812.339q.227-.52.697-.832t1.034-.311q.627 0 1.106.383t.48.998q0 .483-.291.893q-.292.41-.636.75q-.28.255-.523.533q-.242.278-.417.614q-.137.292-.185.593t-.048.624");
}

</style>
