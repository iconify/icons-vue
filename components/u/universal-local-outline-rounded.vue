<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0l5n8qir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:universal-local-outline-rounded" /></template>
<style>
.c0l5n8qir {
  fill: currentColor;
  d: path("M4.616 18h14.769q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T19.385 6H4.615q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173m0 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zM4 18V6zm7.422-6.23q-.23-.23-.23-.578t.23-.577t.578-.23t.578.23t.23.577q0 .349-.23.578q-.23.23-.578.23t-.578-.23M12 7.962q-1.287 0-2.259.891t-.972 2.42q0 .894.687 1.985q.686 1.09 2.01 2.302q.13.105.264.158t.27.053t.27-.053t.265-.159q1.323-1.211 2.01-2.301t.686-1.985q0-1.529-.972-2.42T12 7.962");
}

</style>
