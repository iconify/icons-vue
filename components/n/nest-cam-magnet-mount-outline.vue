<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="novjpibfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-magnet-mount-outline" /></template>
<style>
.novjpibfk {
  fill: currentColor;
  d: path("M22.635 15.992q-.698 0-1.195-.497t-.498-1.195v-4q0-.72.498-1.206q.497-.486 1.195-.486h.692v7.384zm-15.022.919q-.306-.115-.551-.365l-3.388-3.363q-.24-.239-.36-.53q-.122-.292-.122-.594q0-.301.115-.608q.114-.306.364-.551l2.433-2.458q.583-.573 1.316-.87t1.532-.297q1.676 0 2.833 1.157t1.157 2.833q0 .798-.297 1.532t-.87 1.316l-2.427 2.428q-.242.242-.533.363t-.594.121t-.608-.114m1.33-8.636q-.576 0-1.135.235q-.56.234-.99.665l-2.434 2.433q-.173.173-.173.433q0 .259.173.432l3.385 3.385q.173.173.433.173t.433-.173l2.432-2.433q.431-.43.666-.987q.234-.557.234-1.138q0-1.275-.875-2.15t-2.15-.875m8.027 6.614l-.607-.608l1.488-1.489h-3.542v-.884h3.68l-1.596-1.596l.608-.589l2.577 2.558z");
}

</style>
