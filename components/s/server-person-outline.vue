<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci66n9bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:server-person-outline" /></template>
<style>
.ci66n9bij {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21h-2.346l-.924-1.884h-4.25L8.962 21zm0-1h1.711l.923-1.884h5.5L15.692 20h1.712q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T17.404 4H6.616q-.27 0-.443.173T6 4.616v14.769q0 .269.173.442t.443.173m2.076-5.634h6.616V14.2q0-1.05-1.049-1.442T12 12.366t-2.26.392T8.693 14.2zm4.374-4.05q.434-.433.434-1.066t-.434-1.066Q12.633 7.75 12 7.75t-1.066.434T10.5 9.25t.434 1.066q.433.434 1.066.434t1.066-.434M12.02 12");
}

</style>
